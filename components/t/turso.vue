<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/ndceob_-d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ndceob_-d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:turso" /></template>
