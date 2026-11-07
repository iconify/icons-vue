<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j05r12o9z.css';
import '../../css/y/yslzmeb8y.css';
import '../../css/j/jwcfy35xs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j05r12o9z"/><path class="yslzmeb8y"/><path clip-rule="evenodd" class="jwcfy35xs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:phone-calling-bold-duotone" /></template>
