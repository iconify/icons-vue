<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ail5k0ifi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="ail5k0ifi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:musical-keyboard" /></template>
