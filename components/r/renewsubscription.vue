<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b5yb73bwk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":26,"height":26};
const content = `<path class="b5yb73bwk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="wpf:renewsubscription" /></template>
