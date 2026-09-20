<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/be6gqg1nw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path clip-rule="evenodd" class="be6gqg1nw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:ripple-solid" /></template>
