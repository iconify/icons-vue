<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ijmbp0vus.css';
import '../../css/t/td80pac2f.css';
import '../../css/h/h38q_tbmo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ijmbp0vus"/><path class="td80pac2f"/><path class="h38q_tbmo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:marp" /></template>
