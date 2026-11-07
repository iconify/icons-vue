<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b4suqz_5f.css';
import '../../css/m/mrdfzse1o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="b4suqz_5f"/><path class="mrdfzse1o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:plane-2-bold-duotone" /></template>
