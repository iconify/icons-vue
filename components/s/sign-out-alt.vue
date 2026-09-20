<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/ht2tk_has.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="ht2tk_has"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:sign-out-alt" /></template>
