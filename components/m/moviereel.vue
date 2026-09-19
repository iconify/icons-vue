<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ucp01pb_d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="ucp01pb_d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:moviereel" /></template>
