<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/ct9n_cbqw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ct9n_cbqw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bxs:universal-access" /></template>
