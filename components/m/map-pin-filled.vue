<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a_vsq7l3i.css';
import '../../css/j/jcis5eb_p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a_vsq7l3i"/><path clip-rule="evenodd" class="jcis5eb_p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:map-pin-filled" /></template>
