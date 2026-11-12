<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="p05d90bur"/><path class="blm9h9bxz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:user-sync-corner-bulk-round" /></template>
<style>
.blm9h9bxz {
  d: path("M18 16a1 1 0 0 1 0-2h.748a5 5 0 0 0-.195-.106l-.002-.001a3.474 3.474 0 0 0-4.657 1.554a1 1 0 1 1-1.788-.894a5.4 5.4 0 0 1 1.025-1.422A5.464 5.464 0 0 1 20 12.423V12a1 1 0 0 1 2 0v3a1 1 0 0 1-.548.892h-.002l-.001.002h-.001v.001h-.003l-.001.001c-.138.068-.29.104-.444.104ZM2 21c0-1.862.731-3.636 2.05-4.95a7 7 0 0 1 2.225-1.5A6.9 6.9 0 0 1 9 14a1 1 0 0 1 0 2a4.97 4.97 0 0 0-3.536 1.464A4.97 4.97 0 0 0 4 21a1 1 0 0 1-2 0m12 .577V22a1 1 0 0 1-2 0v-3a1 1 0 0 1 .552-.894l.002-.001l.002-.001a1 1 0 0 1 .407-.103h.001L13 18h3a1 1 0 0 1 0 2h-.748a3.47 3.47 0 0 0 4.854-1.447a1 1 0 1 1 1.788.894a5.4 5.4 0 0 1-1.025 1.422a5.4 5.4 0 0 1-1.421 1.025A5.46 5.46 0 0 1 14 21.577");
}

.cuyn6tgcc {
  fill: currentColor;
}

.p05d90bur {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M4 7a5 5 0 1 1 10.001.001A5 5 0 0 1 4 7m6 8v6a1 1 0 0 1-1 1H3a1 1 0 0 1-1-1c0-1.862.731-3.636 2.05-4.95a6.9 6.9 0 0 1 2.225-1.499A6.9 6.9 0 0 1 9 14a1 1 0 0 1 1 1");
}

</style>
