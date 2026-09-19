<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ihkv5i5wa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="ihkv5i5wa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:pimcore" /></template>
