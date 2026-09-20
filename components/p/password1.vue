<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hlf9xobuf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":26,"height":26};
const content = `<path class="hlf9xobuf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="wpf:password1" /></template>
