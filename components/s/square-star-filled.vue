<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p7tvpwjwp.css';
import '../../css/x/x-bzt0blf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p7tvpwjwp"/><path clip-rule="evenodd" class="x-bzt0blf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:square-star-filled" /></template>
