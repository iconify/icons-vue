<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yzgvn4bnp.css';
import '../../css/y/y8j3udq6o.css';
import '../../css/v/vyby-xbyp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="yzgvn4bnp"/><path class="y8j3udq6o"/><path class="vyby-xbyp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:radicle-dark" /></template>
