<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zdx4y4vma.css';
import '../../css/r/rslfarb6v.css';
import '../../css/h/h9hstt17t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zdx4y4vma"/><path class="rslfarb6v"/><path class="h9hstt17t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:private-content-solid" /></template>
