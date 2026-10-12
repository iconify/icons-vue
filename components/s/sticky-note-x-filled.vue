<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x9j0j5byc.css';
import '../../css/s/suv5jb35a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x9j0j5byc"/><path class="suv5jb35a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:sticky-note-x-filled" /></template>
