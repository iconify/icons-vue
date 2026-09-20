<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fp09bcbvv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="fp09bcbvv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:profile-of-person-in-hat" /></template>
