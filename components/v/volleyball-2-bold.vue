<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gk6whjxer.css';
import '../../css/f/f5wyvtl3b.css';
import '../../css/f/fnd8xqbeb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gk6whjxer"/><path class="f5wyvtl3b"/><path class="fnd8xqbeb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:volleyball-2-bold" /></template>
