<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/adhr84b5i.css';
import '../../css/h/htmu1qfhg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="adhr84b5i"/><path class="htmu1qfhg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-high-contrast:mrs-claus" /></template>
