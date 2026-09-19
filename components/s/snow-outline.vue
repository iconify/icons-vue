<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f02eosw7k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="f02eosw7k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="famicons:snow-outline" /></template>
