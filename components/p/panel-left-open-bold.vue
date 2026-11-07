<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j_pkd94hu.css';
import '../../css/o/o-08tibye.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="j_pkd94hu"/><path class="o-08tibye"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:panel-left-open-bold" /></template>
