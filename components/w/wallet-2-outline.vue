<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iyc7oevht.css';
import '../../css/a/abs0vhb6t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iyc7oevht"/><path clip-rule="evenodd" class="abs0vhb6t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:wallet-2-outline" /></template>
