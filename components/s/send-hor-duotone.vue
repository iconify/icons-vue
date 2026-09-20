<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f4ezlsbrm.css';
import '../../css/l/lxlb-0bab.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f4ezlsbrm"/><path class="lxlb-0bab"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lets-icons:send-hor-duotone" /></template>
