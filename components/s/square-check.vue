<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ytv8j6l6t.css';
import '../../css/b/bqhst35fc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ytv8j6l6t"/><path class="bqhst35fc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:square-check" /></template>
