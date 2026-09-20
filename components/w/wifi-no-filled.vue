<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a4sop7z6r.css';
import '../../css/b/b5ugqsb0g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a4sop7z6r"/><path class="b5ugqsb0g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:wifi-no-filled" /></template>
