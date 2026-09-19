<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hcj_ausiv.css';
import '../../css/h/hmp_1pb5l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hcj_ausiv"/><path class="hmp_1pb5l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:wink-tongue-filled" /></template>
