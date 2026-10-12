<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ena9jqbzk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ena9jqbzk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:square-chevron-up-filled" /></template>
