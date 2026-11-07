<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jeuu9nbuy.css';
import '../../css/a/aqn_8jqff.css';
import '../../css/e/empw_abpr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jeuu9nbuy"/><path class="aqn_8jqff"/><path class="empw_abpr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:menu-dots-vertical-bold-duotone" /></template>
