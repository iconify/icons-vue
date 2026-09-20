<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sk-lxbcye.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="sk-lxbcye"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:shield-broken" /></template>
