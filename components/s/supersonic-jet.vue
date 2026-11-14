<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sbvt7cbrr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:supersonic-jet" /></template>
<style>
.sbvt7cbrr {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M2.75 13q0 2.75 2.25 2.75h1.771q-.021.177-.021.375Q6.75 18 8.625 18h5.25q1.875 0 1.875-1.875q0-.215-.025-.406l5.928-1.235q.072-.015.14-.044t.129-.07t.113-.094t.092-.115q.041-.062.068-.13q.028-.069.042-.141q.014-.073.013-.147t-.016-.146q-.022-.107-.074-.204t-.13-.173q-.077-.078-.173-.13q-.097-.052-.204-.074l-6-1.25q-.076-.016-.153-.016H9.39L6.114 7.07q-.051-.074-.119-.134q-.068-.059-.149-.101t-.168-.064Q5.59 6.75 5.5 6.75H3.75q-.072 0-.142.014q-.071.013-.137.04t-.127.065t-.112.089t-.094.108q-.041.058-.071.124q-.029.065-.046.135q-.017.069-.02.141l-.25 5.5z");
}

</style>
