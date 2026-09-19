<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/by140xbel.css';
import '../../css/o/ow_ygzbys.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="by140xbel"/><path class="ow_ygzbys"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bxl:weibo" /></template>
