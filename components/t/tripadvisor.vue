<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q29c6fb3t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="q29c6fb3t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="entypo-social:tripadvisor" /></template>
