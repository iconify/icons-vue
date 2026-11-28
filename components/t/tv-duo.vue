<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s6rfx3q-n.css';
import '../../css/d/dt0cm9dhy.css';
import '../../css/k/kzjvy_biz.css';
import '../../css/a/at0ng4bzo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s6rfx3q-n secondary"/><g class="dt0cm9dhy primary"><path class="kzjvy_biz"/><path class="at0ng4bzo"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:tv-duo" /></template>
