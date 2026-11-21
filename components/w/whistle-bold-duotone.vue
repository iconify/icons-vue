<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="v-frg698a"/><path class="ca4sez0uh"/><path class="ucvcnybnk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:whistle-bold-duotone" /></template>
<style>
.ca4sez0uh {
  fill: currentColor;
  d: path("M8.85059 9.80005C10.0655 9.80015 11.0508 10.7853 11.0508 12.0002C11.0507 13.2151 10.0654 14.2003 8.85059 14.2004C7.63565 14.2004 6.6505 13.2152 6.65039 12.0002C6.65039 10.7852 7.63559 9.80005 8.85059 9.80005Z");
}

.ucvcnybnk {
  fill: currentColor;
  d: path("M11.5996 8.09985C11.5996 8.51407 11.2638 8.84985 10.8496 8.84985C10.4354 8.84985 10.0996 8.51407 10.0996 8.09985V5.50024H11.5996V8.09985Z");
}

.v-frg698a {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M20.2501 5.5C21.1501 5.5 21.6505 6.10039 21.6505 6.90039V8.09961C21.6505 8.89961 21.0499 9.5 20.0499 9.5H14.8507C15.9523 12.144 15.1928 15.198 12.9815 17.0186C10.7702 18.839 7.62744 18.997 5.24423 17.4082C2.86123 15.8194 1.79903 12.8575 2.62899 10.1162C3.45904 7.37489 5.98643 5.5 8.85067 5.5H20.2501ZM8.85067 9.7998C7.63567 9.7998 6.65048 10.785 6.65048 12C6.65049 13.215 7.63568 14.2002 8.85067 14.2002C10.0656 14.2001 11.0509 13.2149 11.0509 12C11.0509 10.7851 10.0656 9.79991 8.85067 9.7998Z");
  opacity: var(--svg-opacity--0-5, 0.5);
}

</style>
