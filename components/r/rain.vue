<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zz7spkb-t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":26,"height":26};
const content = `<path class="zz7spkb-t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="wpf:rain" /></template>
