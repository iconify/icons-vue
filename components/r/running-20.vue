<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qokocnbbw.css';
import '../../css/v/v9e56nbyl.css';
import '../../css/e/eswagv34a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="qokocnbbw"/><path class="v9e56nbyl"/><path class="eswagv34a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:running-20" /></template>
