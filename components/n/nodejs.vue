<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eznpw-5ql.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":898,"height":1024};
const content = `<path class="eznpw-5ql"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:nodejs" /></template>
