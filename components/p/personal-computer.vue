<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/goo_yticv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="goo_yticv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:personal-computer" /></template>
