<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pb1pjibpf.css';
import '../../css/g/g46hbrb1d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="pb1pjibpf"/><path class="g46hbrb1d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:printer-x-filled" /></template>
