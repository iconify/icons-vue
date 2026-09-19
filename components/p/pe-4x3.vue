<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dhcjeybja.css';
import '../../css/o/o9ffdfb9u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":480};
const content = `<path class="dhcjeybja"/><path class="o9ffdfb9u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flag:pe-4x3" /></template>
