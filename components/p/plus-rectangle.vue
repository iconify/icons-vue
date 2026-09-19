<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gc9vhrbpw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="gc9vhrbpw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:plus-rectangle" /></template>
