<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b02oa3b7u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1025,"height":1024};
const content = `<path class="b02oa3b7u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:password" /></template>
