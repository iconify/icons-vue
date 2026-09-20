<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/glz_utbya.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="glz_utbya"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:skull-above-crossed-bones" /></template>
