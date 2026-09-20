<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tefesk3cw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="tefesk3cw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:usertour-light" /></template>
