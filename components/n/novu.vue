<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ea9o-cb6f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ea9o-cb6f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:novu" /></template>
