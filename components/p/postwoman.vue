<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x7gqf0y9i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="x7gqf0y9i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cib:postwoman" /></template>
