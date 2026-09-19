<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kl9d9xb4u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kl9d9xb4u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:model-x-open" /></template>
