<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ah8y2-bwd.css';
import '../../css/n/n5kd2n3_d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ah8y2-bwd"/><path class="n5kd2n3_d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixel:times-square" /></template>
