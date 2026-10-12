<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nl6ol6zfj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="nl6ol6zfj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:receipt-swiss-franc-filled" /></template>
