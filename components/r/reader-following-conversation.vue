<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/beqxhtbkf.css';
import '../../css/w/wd6mpsb3w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="beqxhtbkf"/><path class="wd6mpsb3w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gridicons:reader-following-conversation" /></template>
