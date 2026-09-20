<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/ldk6ger7m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ldk6ger7m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si:remove-from-library-line" /></template>
