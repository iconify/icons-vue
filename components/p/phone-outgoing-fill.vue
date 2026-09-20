<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nm_5gd4wq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nm_5gd4wq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:phone-outgoing-fill" /></template>
