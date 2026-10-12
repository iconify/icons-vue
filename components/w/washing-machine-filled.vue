<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z9gf4ebfj.css';
import '../../css/h/hnvtq9frh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z9gf4ebfj"/><path clip-rule="evenodd" class="hnvtq9frh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:washing-machine-filled" /></template>
