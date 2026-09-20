<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eu3q8dilk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="eu3q8dilk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:zammad-light" /></template>
