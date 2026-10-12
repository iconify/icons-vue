<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d9i3bbuup.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d9i3bbuup"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:worm-filled" /></template>
