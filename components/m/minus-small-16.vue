<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sn-6ucc2n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="sn-6ucc2n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="qlementine-icons:minus-small-16" /></template>
