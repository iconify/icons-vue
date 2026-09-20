<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uqz1v_bkk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uqz1v_bkk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:matrix" /></template>
