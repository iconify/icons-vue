<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a_vsq7l3i.css';
import '../../css/w/w5fdibb6b.css';
import '../../css/p/ps5c3qbsl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a_vsq7l3i"/><path clip-rule="evenodd" class="w5fdibb6b"/><path class="ps5c3qbsl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:map-pin-minus-filled" /></template>
