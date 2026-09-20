<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gfo4vfzqx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:shoe-cleats-sharp" /></template>
<style>
.gfo4vfzqx {
  fill: currentColor;
  d: path("M5.55 21.525q-.684 0-1.335-.261t-1.169-.785l-.04-.06q-.167-.142-.22-.375q-.053-.232.033-.45l1.647-4.161l1.928.69l.289-.823l-1.898-.69l.656-1.677l2.028.748l.245-.862l-1.954-.71l.656-1.676l2.065.746l.308-.829l-2.054-.734l1.167-2.983l2.264.423q.54.113 1.05-.063q.509-.176.905-.572q.421-.427.585-.996t-.02-1.129l-.328-.942l2.223-2.262l6.227 6.352l-1.294 1.35l.823.827l-.746.708l-.78-.81l-1.411 1.437l.804.785l-.72.707l-.778-.779l-3.512 3.562l.76.76l-.738.688l-.71-.74l-1.412 1.417l.735.734l-.72.708l-.728-.729L8.989 19.5l.703.716l-.727.688l-.69-.696l-.327.346q-.517.479-1.118.725t-1.28.246");
}

</style>
