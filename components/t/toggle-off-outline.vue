<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o-8ehqo7a.css';
import '../../css/o/o2uqidcof.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o-8ehqo7a"/><path clip-rule="evenodd" class="o2uqidcof"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="basil:toggle-off-outline" /></template>
