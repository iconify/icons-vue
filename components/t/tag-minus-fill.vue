<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b7ixe7qvc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b7ixe7qvc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mage:tag-minus-fill" /></template>
