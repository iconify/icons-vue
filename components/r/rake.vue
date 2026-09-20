<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u1-r8ou6u.css';
import '../../css/r/rjpmsmbhz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u1-r8ou6u"/><path class="rjpmsmbhz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:rake" /></template>
