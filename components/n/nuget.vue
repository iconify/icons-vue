<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uow25q6ka.css';
import '../../css/i/iyj96ne-g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<circle class="uow25q6ka"/><path class="iyj96ne-g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:nuget" /></template>
