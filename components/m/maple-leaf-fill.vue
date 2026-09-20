<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pzcnwk9yk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pzcnwk9yk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:maple-leaf-fill" /></template>
