<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lg8fk_74i.css';
import '../../css/h/hjncjwk0j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lg8fk_74i"/><path clip-rule="evenodd" class="hjncjwk0j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:mailbox-filled" /></template>
