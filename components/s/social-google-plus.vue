<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qhmipyblw.css';
import '../../css/v/vztvh8bnd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":100,"height":100};
const content = `<path class="qhmipyblw"/><path class="vztvh8bnd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="foundation:social-google-plus" /></template>
