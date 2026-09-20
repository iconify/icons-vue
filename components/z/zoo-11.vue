<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b1xz3lbje.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":11,"height":11};
const content = `<path class="b1xz3lbje"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="maki:zoo-11" /></template>
