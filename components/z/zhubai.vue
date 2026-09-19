<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e_ayi0ben.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="e_ayi0ben"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:zhubai" /></template>
