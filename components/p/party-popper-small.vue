<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/at_li1b0i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="at_li1b0i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:party-popper-small" /></template>
