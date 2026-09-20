<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tc5tmtbuk.css';
import '../../css/j/jb32k7b4k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tc5tmtbuk"/><path class="jb32k7b4k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:museum-filled" /></template>
