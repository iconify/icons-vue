<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ugqc2tbhk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ugqc2tbhk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:square-asterisk" /></template>
