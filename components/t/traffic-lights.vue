<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/an__cwb5h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="an__cwb5h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="at-icons:traffic-lights" /></template>
