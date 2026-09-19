<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bv26y9bqo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="bv26y9bqo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:negative-dynamics" /></template>
