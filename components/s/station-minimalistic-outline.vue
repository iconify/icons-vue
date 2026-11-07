<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zpqc5xbsu.css';
import '../../css/h/h2iv_1boz.css';
import '../../css/g/g3j7u010m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zpqc5xbsu"/><path class="h2iv_1boz"/><path clip-rule="evenodd" class="g3j7u010m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:station-minimalistic-outline" /></template>
