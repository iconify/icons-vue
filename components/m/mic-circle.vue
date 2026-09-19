<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a4ww0ra-t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="a4ww0ra-t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:mic-circle" /></template>
