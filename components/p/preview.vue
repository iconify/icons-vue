<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vlmnb0b7u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1025};
const content = `<path class="vlmnb0b7u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:preview" /></template>
