<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b-s5hqb3c.css';
import '../../css/b/bis1pebdp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="b-s5hqb3c"/><path class="bis1pebdp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:shop-minimalistic-outline" /></template>
