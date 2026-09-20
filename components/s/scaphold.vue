<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":274};
const content = `<path class="fcw8lm8se"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="logos:scaphold" /></template>
<style>
.fcw8lm8se {
  fill: var(--svg-color--00aca1, #00ACA1);
  d: path("M206.306-.001V18.07H0v73.185h17.669v21.083H0v48.791h224.076v21.082h-17.77v21.986H0v69.271h51.502v-19.276H256v-71.981h-16.263v-21.082H256v-48.791H33.331V91.255H51.2V68.969H256V-.001z");
}

</style>
