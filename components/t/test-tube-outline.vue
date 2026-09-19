<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jv1ykgv5n.css';
import '../../css/x/x6w6rpbzx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="jv1ykgv5n"/><path clip-rule="evenodd" class="x6w6rpbzx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cuida:test-tube-outline" /></template>
