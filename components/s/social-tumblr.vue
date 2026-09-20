<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ao59tsqbv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="ao59tsqbv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-line-icons:social-tumblr" /></template>
