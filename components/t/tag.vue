<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f5jm7bc9i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="f5jm7bc9i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:tag" /></template>
