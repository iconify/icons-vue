<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gupyo-9yt.css';
import '../../css/l/li2ndrlth.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gupyo-9yt"/><path class="li2ndrlth"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bxl:upi" /></template>
