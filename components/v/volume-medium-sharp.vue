<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uwr0ifb7o.css';
import '../../css/a/ahflddu7k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="uwr0ifb7o"/><path class="ahflddu7k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="famicons:volume-medium-sharp" /></template>
