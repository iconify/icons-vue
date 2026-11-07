<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j_6cwfbbm.css';
import '../../css/z/zoahz159d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j_6cwfbbm"/><path clip-rule="evenodd" class="zoahz159d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:panel-left-open-outline" /></template>
