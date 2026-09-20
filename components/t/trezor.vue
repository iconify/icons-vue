<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lfrl_cb_l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lfrl_cb_l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:trezor" /></template>
