<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f-xue7lql.css';
import '../../css/r/rh9letwnk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="f-xue7lql"/><path class="rh9letwnk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:volume-high-sharp" /></template>
