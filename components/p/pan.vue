<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s5nod8qop.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="s5nod8qop"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:pan" /></template>
