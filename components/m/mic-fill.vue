<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/ggyqufb9a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="ggyqufb9a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:mic-fill" /></template>
