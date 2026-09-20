<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/byp3dbcaf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="byp3dbcaf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-line-icons:social-reddit" /></template>
