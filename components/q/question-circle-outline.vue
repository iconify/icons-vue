<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lt_dvue1n.css';
import '../../css/t/ts_bt_bky.css';
import '../../css/d/du6sep0xm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lt_dvue1n"/><path class="ts_bt_bky"/><path clip-rule="evenodd" class="du6sep0xm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:question-circle-outline" /></template>
