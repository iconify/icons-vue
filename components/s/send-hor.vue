<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mk_k-5bjk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mk_k-5bjk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lets-icons:send-hor" /></template>
