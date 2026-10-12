<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b7axs0bsw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b7axs0bsw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:mouse-pointer-2-filled" /></template>
