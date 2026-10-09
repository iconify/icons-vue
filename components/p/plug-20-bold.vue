<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xt_zhw2mi.css';
import '../../css/i/i_3ks9poz.css';
import '../../css/q/qbyv8qirk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="xt_zhw2mi"/><path class="i_3ks9poz"/><path class="qbyv8qirk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:plug-20-bold" /></template>
