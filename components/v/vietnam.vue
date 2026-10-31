<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u07gqdk2e.css';
import '../../css/b/buahpzh7c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":30,"height":24};
const content = `<path class="u07gqdk2e"/><path class="buahpzh7c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler-flags:vietnam" /></template>
