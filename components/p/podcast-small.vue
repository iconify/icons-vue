<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sni5zobtk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="sni5zobtk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:podcast-small" /></template>
