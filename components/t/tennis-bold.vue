<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a8d273bat.css';
import '../../css/b/b81mgxb0y.css';
import '../../css/y/y8nlgsb7k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a8d273bat"/><path class="b81mgxb0y"/><path class="y8nlgsb7k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:tennis-bold" /></template>
