<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/te1hwkbud.css';
import '../../css/b/bkh5a45lp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="te1hwkbud"/><path class="bkh5a45lp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:psychology-filled" /></template>
