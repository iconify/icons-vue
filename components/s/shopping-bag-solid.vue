<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jg1y38x-a.css';
import '../../css/p/p9aucsbot.css';
import '../../css/m/m2o3sh-9c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="clr-i-solid clr-i-solid-path-1 jg1y38x-a"/><path class="clr-i-solid clr-i-solid-path-2 p9aucsbot"/><path class="m2o3sh-9c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="clarity:shopping-bag-solid" /></template>
