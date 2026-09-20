<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xcm44_rqe.css';
import '../../css/g/gh05_sajp.css';
import '../../css/o/o7mpebc-w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xcm44_rqe"/><path class="gh05_sajp"/><path class="o7mpebc-w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixel:shuffle-solid" /></template>
