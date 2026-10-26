<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dodx40jvk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="dodx40jvk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="doodle-icons:moon-stars" /></template>
