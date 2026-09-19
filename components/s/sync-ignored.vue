<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/thlvqn8bb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="thlvqn8bb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="codicon:sync-ignored" /></template>
