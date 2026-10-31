<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/ber-z8qlk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ber-z8qlk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:x-circle-gloss" /></template>
