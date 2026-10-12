<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/auv8y4bny.css';
import '../../css/m/mhso12ngf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="auv8y4bny"/><path class="mhso12ngf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:package-minus-filled" /></template>
