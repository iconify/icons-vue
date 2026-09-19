<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sx561ngds.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="sx561ngds"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:sign-out-alt" /></template>
