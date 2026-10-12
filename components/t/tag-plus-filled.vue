<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/ng18x5bhl.css';
import '../../css/b/bdg69fb8a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ng18x5bhl"/><path class="bdg69fb8a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:tag-plus-filled" /></template>
