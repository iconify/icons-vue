<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b20sknb1d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="b20sknb1d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si:reorder-alt-fill" /></template>
