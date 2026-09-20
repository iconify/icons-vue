<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/btr0sh55s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="btr0sh55s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="radix-icons:speaker-quiet" /></template>
