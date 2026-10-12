<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aa-h6knvf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="aa-h6knvf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:tickets-filled" /></template>
