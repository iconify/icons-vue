<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b__vzjb9s.css';
import '../../css/t/tvb2i4bux.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="b__vzjb9s"/><path class="tvb2i4bux"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lets-icons:shop-duotone" /></template>
