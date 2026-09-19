<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pve9mubqw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="pve9mubqw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:robot" /></template>
